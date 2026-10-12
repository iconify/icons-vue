<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv9s_nlzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fv9s_nlzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-trending-20" /></template>
