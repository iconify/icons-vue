<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhx6xt5an.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhx6xt5an"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:headphones" /></template>
