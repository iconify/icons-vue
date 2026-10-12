<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-4szcb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u-4szcb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:decimal-20" /></template>
