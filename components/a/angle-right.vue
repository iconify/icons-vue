<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f64paxb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f64paxb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:angle-right" /></template>
