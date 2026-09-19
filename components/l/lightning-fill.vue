<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukz7ccbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ukz7ccbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:lightning-fill" /></template>
