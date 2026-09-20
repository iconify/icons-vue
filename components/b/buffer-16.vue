<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx5tgy66g.css';
import '../../css/g/gx3qh1bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kx5tgy66g"/><path class="gx3qh1bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:buffer-16" /></template>
