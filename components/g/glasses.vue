<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pagr-vblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pagr-vblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:glasses" /></template>
