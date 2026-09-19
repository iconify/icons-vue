<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5x2r3blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p5x2r3blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-number-sign-small" /></template>
