<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpc-6mina.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpc-6mina"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horseshoe" /></template>
