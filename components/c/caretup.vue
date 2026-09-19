<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfvwfdc9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":9};
const content = `<path class="vfvwfdc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:caretup" /></template>
