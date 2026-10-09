<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptvb_sb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ptvb_sb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-drizzle-20" /></template>
