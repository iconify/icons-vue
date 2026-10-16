<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjnt2fbgz.css';
import '../../css/x/xinwgk1sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rjnt2fbgz"/><path class="xinwgk1sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-tax-20" /></template>
