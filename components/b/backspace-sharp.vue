<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp6e1w2wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sp6e1w2wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:backspace-sharp" /></template>
