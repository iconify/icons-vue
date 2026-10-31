<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi8-l0bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi8-l0bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clipboard-x-gloss" /></template>
