<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s26cq-8xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="s26cq-8xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dumpster-fire" /></template>
