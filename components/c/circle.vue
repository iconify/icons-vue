<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piookjxpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piookjxpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:circle" /></template>
