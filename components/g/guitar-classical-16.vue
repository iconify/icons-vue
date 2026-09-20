<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1cd9e3yd.css';
import '../../css/l/lsqebab9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b1cd9e3yd"/><path class="lsqebab9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-classical-16" /></template>
