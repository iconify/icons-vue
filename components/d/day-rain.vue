<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iddj-1bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="iddj-1bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:day-rain" /></template>
