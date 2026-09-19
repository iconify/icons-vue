<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbc_go3dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbc_go3dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:json" /></template>
