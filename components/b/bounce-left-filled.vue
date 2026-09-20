<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oytpm0ile.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oytpm0ile"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bounce-left-filled" /></template>
