<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnv2b63dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnv2b63dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-dong" /></template>
