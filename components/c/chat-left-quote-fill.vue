<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0ustobjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k0ustobjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-left-quote-fill" /></template>
