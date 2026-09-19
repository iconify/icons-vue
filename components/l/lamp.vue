<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz9vh5b-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":448};
const content = `<path class="vz9vh5b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:lamp" /></template>
