<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5mp2kwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":24};
const content = `<path class="zw5mp2kwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:line" /></template>
