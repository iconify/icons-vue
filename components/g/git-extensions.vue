<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2swdhylm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2swdhylm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:git-extensions" /></template>
