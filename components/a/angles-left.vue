<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkym8bcai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkym8bcai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:angles-left" /></template>
