<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vseh-l-0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="vseh-l-0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:indent" /></template>
