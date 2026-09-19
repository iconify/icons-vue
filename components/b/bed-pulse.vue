<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3zptuyzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="f3zptuyzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bed-pulse" /></template>
