<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maer_5kur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maer_5kur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:button-pointer" /></template>
