<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peplw6b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="peplw6b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flagstick-with-pennant" /></template>
