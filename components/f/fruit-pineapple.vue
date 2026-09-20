<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/texu0db1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="texu0db1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fruit-pineapple" /></template>
