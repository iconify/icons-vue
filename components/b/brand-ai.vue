<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmrhozbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bmrhozbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:brand-ai" /></template>
