<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zej5dm5-i.css';
import '../../css/a/abnnwxzhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zej5dm5-i"/><path clip-rule="evenodd" class="abnnwxzhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-bold-duotone" /></template>
