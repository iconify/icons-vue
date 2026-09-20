<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqqg_zbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqqg_zbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:building-columns" /></template>
