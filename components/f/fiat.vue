<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-f68p8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7-f68p8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fiat" /></template>
