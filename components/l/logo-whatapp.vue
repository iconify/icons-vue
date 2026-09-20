<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x74im5bbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x74im5bbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:logo-whatapp" /></template>
