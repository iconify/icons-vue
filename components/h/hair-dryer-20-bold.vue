<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc5w0p7ef.css';
import '../../css/j/jnqm95cmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hc5w0p7ef"/><path class="jnqm95cmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hair-dryer-20-bold" /></template>
