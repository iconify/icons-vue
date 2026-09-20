<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgi-2-fci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgi-2-fci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:adblock" /></template>
