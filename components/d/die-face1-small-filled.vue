<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu6gvgk1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vu6gvgk1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:die-face1-small-filled" /></template>
