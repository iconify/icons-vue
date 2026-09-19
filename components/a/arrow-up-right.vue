<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4nrrlban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y4nrrlban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:arrow-up-right" /></template>
