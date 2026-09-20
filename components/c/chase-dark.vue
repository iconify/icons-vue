<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcp4wuuyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcp4wuuyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chase-dark" /></template>
