<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqd0yrbhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tqd0yrbhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bring-to-front-one" /></template>
