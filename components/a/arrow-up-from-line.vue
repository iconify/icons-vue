<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdq-tsbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zdq-tsbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-up-from-line" /></template>
