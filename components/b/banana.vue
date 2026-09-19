<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0u_4izij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="v0u_4izij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:banana" /></template>
