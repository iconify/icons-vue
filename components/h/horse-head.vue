<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg-zz8hri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bg-zz8hri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:horse-head" /></template>
