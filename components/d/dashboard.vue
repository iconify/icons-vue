<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncx4c8byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncx4c8byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dashboard" /></template>
