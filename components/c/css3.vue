<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5y6pnb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q5y6pnb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:css3" /></template>
