<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2b3vi6yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e2b3vi6yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:arrow-redo-circle-sharp" /></template>
