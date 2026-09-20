<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxpig_jqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxpig_jqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-light-high" /></template>
