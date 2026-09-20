<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m68fv6b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m68fv6b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-dropping-circles" /></template>
