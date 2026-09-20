<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzuzk3k6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzuzk3k6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:engine-temperature-warning" /></template>
