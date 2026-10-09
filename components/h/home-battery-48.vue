<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0yys_sjp.css';
import '../../css/g/g3j-8gbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0yys_sjp"/><path class="g3j-8gbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:home-battery-48" /></template>
