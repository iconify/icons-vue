<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asbux8b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asbux8b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-left-gloss" /></template>
