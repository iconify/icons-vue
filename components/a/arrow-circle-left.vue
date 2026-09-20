<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge2r--jhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ge2r--jhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-circle-left" /></template>
