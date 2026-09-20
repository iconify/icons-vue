<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1a6a-b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1a6a-b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-7" /></template>
