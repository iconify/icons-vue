<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzb79obee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzb79obee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cubes" /></template>
