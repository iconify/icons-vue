<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3z3e5bjw.css';
import '../../css/q/qqzqv2f4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u3z3e5bjw"/><path class="qqzqv2f4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-right-to-line-20" /></template>
