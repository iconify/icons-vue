<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myggo7b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myggo7b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-tr-circled" /></template>
