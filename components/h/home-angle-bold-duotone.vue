<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gswtq35or.css';
import '../../css/z/zyfh3yufc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gswtq35or"/><path class="zyfh3yufc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:home-angle-bold-duotone" /></template>
