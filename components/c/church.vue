<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws1o19b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ws1o19b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:church" /></template>
