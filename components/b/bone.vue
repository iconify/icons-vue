<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqp55hbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hqp55hbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bone" /></template>
