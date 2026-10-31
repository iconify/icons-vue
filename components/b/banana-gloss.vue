<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-zew7byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-zew7byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:banana-gloss" /></template>
