<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrdvnvboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrdvnvboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:caret-left-square" /></template>
