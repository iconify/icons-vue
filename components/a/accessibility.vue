<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4ia2pgnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ia2pgnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:accessibility" /></template>
