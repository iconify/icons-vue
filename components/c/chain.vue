<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj4wpusjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jj4wpusjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:chain" /></template>
