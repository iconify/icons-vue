<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bttfc0bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bttfc0bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:dataflows-link" /></template>
