<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_blhsbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x_blhsbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:coffin-with-exclamation-point" /></template>
