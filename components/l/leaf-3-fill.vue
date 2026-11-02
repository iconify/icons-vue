<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue9d2bbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9d2bbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:leaf-3-fill" /></template>
