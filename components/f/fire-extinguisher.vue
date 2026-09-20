<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr_1l7bfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kr_1l7bfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fire-extinguisher" /></template>
