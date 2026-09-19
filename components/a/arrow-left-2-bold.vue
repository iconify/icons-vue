<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcmxhtbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcmxhtbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-left-2-bold" /></template>
