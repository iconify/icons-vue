<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hig-594lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hig-594lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-2-filled" /></template>
