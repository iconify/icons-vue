<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqssqub7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="lqssqub7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:droplet" /></template>
