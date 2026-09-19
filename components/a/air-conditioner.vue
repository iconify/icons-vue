<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whznf4bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whznf4bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:air-conditioner" /></template>
