<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjs0b7ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjs0b7ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:city-alt" /></template>
