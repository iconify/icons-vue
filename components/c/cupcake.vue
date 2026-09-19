<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i644t-bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i644t-bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cupcake" /></template>
