<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx_6pdo2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yx_6pdo2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:institutional-building" /></template>
