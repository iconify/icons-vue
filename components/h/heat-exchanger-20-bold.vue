<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewxalfyww.css';
import '../../css/j/jxwwvvbjb.css';
import '../../css/t/tp0bwlbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewxalfyww"/><path class="jxwwvvbjb"/><path class="tp0bwlbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-exchanger-20-bold" /></template>
