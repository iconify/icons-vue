<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bje2-jnxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="bje2-jnxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-slash" /></template>
