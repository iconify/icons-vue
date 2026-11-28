<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vki2y12ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vki2y12ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:list-play" /></template>
