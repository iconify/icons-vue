<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsb8gwlib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zsb8gwlib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:editor-outdent" /></template>
