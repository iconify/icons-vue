<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzsbmhebc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzsbmhebc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-14-filled" /></template>
