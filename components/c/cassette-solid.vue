<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz2v2pcnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz2v2pcnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cassette-solid" /></template>
