<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu6p_sb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":705,"height":1024};
const content = `<path class="bu6p_sb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:heavymetal" /></template>
