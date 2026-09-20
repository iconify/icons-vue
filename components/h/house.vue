<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y45kiiu1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="y45kiiu1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:house" /></template>
