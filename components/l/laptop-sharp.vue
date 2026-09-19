<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co_jnenov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co_jnenov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:laptop-sharp" /></template>
