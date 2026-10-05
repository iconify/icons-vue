<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o36b4-bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o36b4-bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bear-and-exclamation-point" /></template>
