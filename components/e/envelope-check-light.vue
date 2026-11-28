<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks8oc-16p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ks8oc-16p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:envelope-check-light" /></template>
