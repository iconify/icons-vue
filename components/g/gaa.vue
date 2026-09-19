<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hul69bcrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hul69bcrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:gaa" /></template>
