<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozo9kkyme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1080,"height":1080};
const content = `<path class="ozo9kkyme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:evidence-dev" /></template>
