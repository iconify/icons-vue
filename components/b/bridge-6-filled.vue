<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxiapbc1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxiapbc1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bridge-6-filled" /></template>
