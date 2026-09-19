<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg-5y4bmb.css';
import '../../css/p/pv1m9o-dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cg-5y4bmb"/><path class="pv1m9o-dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:comments" /></template>
