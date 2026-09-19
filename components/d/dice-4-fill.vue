<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7fa9ebby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w7fa9ebby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:dice-4-fill" /></template>
