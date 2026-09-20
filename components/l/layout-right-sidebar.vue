<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpoml5myf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpoml5myf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:layout-right-sidebar" /></template>
