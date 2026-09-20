<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li5obibqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="li5obibqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:alarm" /></template>
