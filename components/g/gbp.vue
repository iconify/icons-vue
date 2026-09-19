<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx2w4zb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1408};
const content = `<path class="mx2w4zb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gbp" /></template>
