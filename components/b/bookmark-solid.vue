<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6q0xsb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i6q0xsb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bookmark-solid" /></template>
