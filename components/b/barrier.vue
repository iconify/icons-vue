<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_8zmqbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i_8zmqbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:barrier" /></template>
