<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j35y4j_7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j35y4j_7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:image" /></template>
