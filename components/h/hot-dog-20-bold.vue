<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnd4qacir.css';
import '../../css/x/x43eb82dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tnd4qacir"/><path class="x43eb82dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hot-dog-20-bold" /></template>
