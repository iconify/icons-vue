<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx32ncc0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kx32ncc0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bunker" /></template>
