<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_qitj33o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="t_qitj33o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:house" /></template>
