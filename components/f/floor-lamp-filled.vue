<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mccejepmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mccejepmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:floor-lamp-filled" /></template>
