<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9270-b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c9270-b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:globe-outline" /></template>
