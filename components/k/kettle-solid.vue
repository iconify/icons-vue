<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld262t2kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld262t2kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:kettle-solid" /></template>
