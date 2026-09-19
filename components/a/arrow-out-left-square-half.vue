<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxf1odf7b.css';
import '../../css/s/sgoebkv5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxf1odf7b"/><path class="sgoebkv5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-left-square-half" /></template>
