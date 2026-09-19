<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjqcbzv4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="bjqcbzv4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:l" /></template>
