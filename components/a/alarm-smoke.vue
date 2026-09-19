<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg2_2cs5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg2_2cs5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alarm-smoke" /></template>
