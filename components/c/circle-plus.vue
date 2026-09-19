<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9eriqbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9eriqbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:circle-plus" /></template>
