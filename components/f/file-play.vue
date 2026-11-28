<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op7ctac_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op7ctac_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:file-play" /></template>
