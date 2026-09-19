<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doo177jjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":24};
const content = `<path class="doo177jjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:helicopter" /></template>
