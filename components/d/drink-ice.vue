<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fguutacle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fguutacle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:drink-ice" /></template>
