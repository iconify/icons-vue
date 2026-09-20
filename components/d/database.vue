<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwuqptv4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uwuqptv4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:database" /></template>
