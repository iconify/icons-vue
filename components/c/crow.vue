<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7n9o0bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="a7n9o0bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:crow" /></template>
