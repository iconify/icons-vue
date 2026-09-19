<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0_a_7k0f.css';
import '../../css/w/wk4cq8krv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0_a_7k0f"/><path class="wk4cq8krv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:at-circle-sharp" /></template>
