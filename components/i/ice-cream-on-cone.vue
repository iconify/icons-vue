<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isgk0lbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="isgk0lbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ice-cream-on-cone" /></template>
