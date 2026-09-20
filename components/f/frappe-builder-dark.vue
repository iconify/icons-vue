<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-4xjcc1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-4xjcc1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-builder-dark" /></template>
