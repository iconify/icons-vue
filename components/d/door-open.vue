<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpop_tbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="hpop_tbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:door-open" /></template>
