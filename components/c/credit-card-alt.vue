<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw5qx8bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="nw5qx8bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:credit-card-alt" /></template>
