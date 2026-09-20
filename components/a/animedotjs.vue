<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1wjkvtye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1wjkvtye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:animedotjs" /></template>
