<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7q0rkbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="v7q0rkbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:globe" /></template>
