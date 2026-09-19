<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx96-_bvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx96-_bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:bowl-food-outline" /></template>
