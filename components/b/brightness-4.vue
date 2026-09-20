<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bguw7rb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bguw7rb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:brightness-4" /></template>
