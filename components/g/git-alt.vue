<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g79_qq09y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="g79_qq09y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:git-alt" /></template>
