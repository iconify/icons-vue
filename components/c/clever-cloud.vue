<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti6iz-nxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti6iz-nxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clever-cloud" /></template>
