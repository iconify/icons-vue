<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uim1q5fzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uim1q5fzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-back-sharp" /></template>
