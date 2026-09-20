<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcrajss1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="hcrajss1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:enter" /></template>
