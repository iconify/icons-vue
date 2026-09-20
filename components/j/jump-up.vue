<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5joxus6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="j5joxus6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:jump-up" /></template>
