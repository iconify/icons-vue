<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkgk1dcfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkgk1dcfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ethiopianairlines" /></template>
