<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw69zccsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw69zccsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list3" /></template>
