<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqg22qc_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bqg22qc_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:download" /></template>
