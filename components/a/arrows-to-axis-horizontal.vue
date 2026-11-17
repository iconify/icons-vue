<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aczw4yb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aczw4yb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrows-to-axis-horizontal" /></template>
