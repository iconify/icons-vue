<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc7k2r7yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7k2r7yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bag-check" /></template>
