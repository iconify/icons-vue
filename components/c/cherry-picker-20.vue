<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvfa_-8wt.css';
import '../../css/q/qlwn4rb9s.css';
import '../../css/y/y1kkhac6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vvfa_-8wt"/><path class="qlwn4rb9s"/><path class="y1kkhac6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cherry-picker-20" /></template>
