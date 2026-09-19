<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye3crjnhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye3crjnhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-right" /></template>
