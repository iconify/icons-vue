<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idif-hbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idif-hbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:add" /></template>
