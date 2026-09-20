<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_c6c0bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c_c6c0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:circle-stroked" /></template>
