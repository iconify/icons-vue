<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sequ2mpmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sequ2mpmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:golf-solid" /></template>
