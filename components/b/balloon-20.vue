<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr413t_mq.css';
import '../../css/b/bccw67g_w.css';
import '../../css/c/c0qc5jl9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mr413t_mq"/><path class="bccw67g_w"/><path class="c0qc5jl9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:balloon-20" /></template>
