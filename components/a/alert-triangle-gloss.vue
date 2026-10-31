<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8wzu_1ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8wzu_1ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alert-triangle-gloss" /></template>
