<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_v7ydg7q.css';
import '../../css/e/e-qkt480u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r_v7ydg7q"/><path clip-rule="evenodd" class="e-qkt480u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:layout-screen-horizontal-16" /></template>
