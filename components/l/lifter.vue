<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iutr1k6lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iutr1k6lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:lifter" /></template>
