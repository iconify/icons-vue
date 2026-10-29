<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0m9t2hdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0m9t2hdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-solid" /></template>
