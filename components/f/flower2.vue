<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fce7lrm6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fce7lrm6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flower2" /></template>
