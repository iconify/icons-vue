<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix7slo6_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ix7slo6_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrowshape-turn-up-right" /></template>
