<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gena9bc0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gena9bc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bag-outline" /></template>
