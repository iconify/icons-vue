<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te5-__5uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te5-__5uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-11-filled" /></template>
