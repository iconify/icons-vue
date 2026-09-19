<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isade3bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="isade3bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:equals" /></template>
