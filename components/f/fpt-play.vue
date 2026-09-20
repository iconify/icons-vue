<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj4o9achs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":279.62,"height":279.9};
const content = `<path class="vj4o9achs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fpt-play" /></template>
