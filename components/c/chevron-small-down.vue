<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-cg9db9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n-cg9db9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:chevron-small-down" /></template>
