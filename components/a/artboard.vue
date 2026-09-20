<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frt7vtf9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frt7vtf9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:artboard" /></template>
