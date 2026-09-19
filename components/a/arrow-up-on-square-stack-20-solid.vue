<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz6yhgbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rz6yhgbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-on-square-stack-20-solid" /></template>
