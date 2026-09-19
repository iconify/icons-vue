<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be94h47pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="be94h47pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:droplet-slash" /></template>
