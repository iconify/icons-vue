<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj9cwm6hq.css';
import '../../css/d/d66d9mkgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cj9cwm6hq"/><path class="d66d9mkgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:clipboard" /></template>
