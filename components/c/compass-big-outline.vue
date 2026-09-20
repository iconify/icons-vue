<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbnbyk57b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbnbyk57b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:compass-big-outline" /></template>
