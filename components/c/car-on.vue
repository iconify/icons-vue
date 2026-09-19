<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_k3-08ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r_k3-08ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:car-on" /></template>
