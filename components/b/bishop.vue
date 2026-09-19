<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktm36pb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="ktm36pb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bishop" /></template>
