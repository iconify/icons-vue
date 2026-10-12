<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0h02gu-q.css';
import '../../css/z/zfr7hdc4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r0h02gu-q"/><path class="zfr7hdc4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hurricane-20-bold" /></template>
