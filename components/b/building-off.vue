<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p35k1cbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p35k1cbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-off" /></template>
