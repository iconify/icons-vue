<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvj8svzab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rvj8svzab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:flattr" /></template>
