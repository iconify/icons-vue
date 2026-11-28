<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjcevpbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjcevpbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dna" /></template>
