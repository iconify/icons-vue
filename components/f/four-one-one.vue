<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n65uq_b4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n65uq_b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-one-one" /></template>
