<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw8ctlbtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aw8ctlbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:fastapi-wordmark" /></template>
