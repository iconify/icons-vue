<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th5y43rma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="th5y43rma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:egg" /></template>
