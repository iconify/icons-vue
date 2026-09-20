<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d06s-2bqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d06s-2bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:compiling-outline" /></template>
