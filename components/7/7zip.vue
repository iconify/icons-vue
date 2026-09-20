<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvvdxrb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvvdxrb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:7zip" /></template>
