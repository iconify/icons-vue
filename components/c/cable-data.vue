<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn27_lvoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn27_lvoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cable-data" /></template>
