<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6xt5c87v.css';
import '../../css/n/n_fmt7b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="j6xt5c87v"/><path class="n_fmt7b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:football-outline" /></template>
