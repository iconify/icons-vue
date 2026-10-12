<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrfwqwnbz.css';
import '../../css/i/in3blmbct.css';
import '../../css/c/cg_uq7u7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vrfwqwnbz"/><path class="in3blmbct"/><path class="cg_uq7u7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:angle-grinder-20-bold" /></template>
