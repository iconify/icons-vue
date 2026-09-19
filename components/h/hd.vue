<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7r_92krw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7r_92krw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hd" /></template>
