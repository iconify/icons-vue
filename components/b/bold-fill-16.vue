<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_1s8bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ec_1s8bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bold-fill-16" /></template>
