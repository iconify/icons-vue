<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpizigbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bpizigbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:draft2digital" /></template>
