<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckf6p_b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ckf6p_b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:baseball-11" /></template>
