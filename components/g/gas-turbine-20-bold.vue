<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuvrm472q.css';
import '../../css/n/nzmy_41cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yuvrm472q"/><path class="nzmy_41cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-turbine-20-bold" /></template>
