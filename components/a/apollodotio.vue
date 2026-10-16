<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp60qnapt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":303,"height":303};
const content = `<path class="sp60qnapt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apollodotio" /></template>
