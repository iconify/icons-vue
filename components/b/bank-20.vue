<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm24f5buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jm24f5buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bank-20" /></template>
