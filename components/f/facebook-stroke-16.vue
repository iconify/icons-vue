<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwswi3zqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lwswi3zqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:facebook-stroke-16" /></template>
