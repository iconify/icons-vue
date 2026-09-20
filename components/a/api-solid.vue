<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2cn_jb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2cn_jb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:api-solid" /></template>
