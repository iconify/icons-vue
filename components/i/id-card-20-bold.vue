<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn86m-bcf.css';
import '../../css/y/ydr36qd6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pn86m-bcf"/><path class="ydr36qd6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:id-card-20-bold" /></template>
