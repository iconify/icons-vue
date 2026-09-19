<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhqe3lmxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xhqe3lmxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:align-left" /></template>
