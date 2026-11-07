<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c08ckl39y.css';
import '../../css/f/fdtedkyxq.css';
import '../../css/r/re8-x0t_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c08ckl39y"/><path class="fdtedkyxq"/><path class="re8-x0t_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filters-bold" /></template>
