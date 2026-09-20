<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt01g1b5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt01g1b5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:database-2" /></template>
