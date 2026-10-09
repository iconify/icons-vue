<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo0s-wbvc.css';
import '../../css/t/t0ztzgb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lo0s-wbvc"/><path class="t0ztzgb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-open-20" /></template>
