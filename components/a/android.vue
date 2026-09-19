<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj_wpibuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uj_wpibuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:android" /></template>
