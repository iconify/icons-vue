<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh9q0kbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sh9q0kbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:branch" /></template>
