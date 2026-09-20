<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz6lxvbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yz6lxvbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:align-top-1" /></template>
