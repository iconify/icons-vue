<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpbo3xbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpbo3xbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-arrow-out-down-right" /></template>
