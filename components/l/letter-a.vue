<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb8dg2b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb8dg2b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-a" /></template>
