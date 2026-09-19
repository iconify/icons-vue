<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi0g28_vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="zi0g28_vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:long-arrow-alt-left" /></template>
