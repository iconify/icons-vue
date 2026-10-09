<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjnplr66g.css';
import '../../css/g/gziv7kbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jjnplr66g"/><path class="gziv7kbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-range-20" /></template>
