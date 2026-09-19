<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_--k2e7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u_--k2e7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bible" /></template>
