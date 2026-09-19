<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atou-fymc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="atou-fymc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:building-circle-check" /></template>
