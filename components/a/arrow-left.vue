<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z31n7sf4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1600};
const content = `<path class="z31n7sf4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-left" /></template>
