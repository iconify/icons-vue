<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-secxbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-secxbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:like" /></template>
