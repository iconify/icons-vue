<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6b7aqblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6b7aqblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:accuweather" /></template>
