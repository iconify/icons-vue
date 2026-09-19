<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg6srub4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fg6srub4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-italic" /></template>
