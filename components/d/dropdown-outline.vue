<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo8h7hb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo8h7hb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:dropdown-outline" /></template>
