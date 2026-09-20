<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa3k2bkey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa3k2bkey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ens" /></template>
