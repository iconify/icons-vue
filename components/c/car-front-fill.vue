<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwuva2m7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wwuva2m7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:car-front-fill" /></template>
