<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flur0ubwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flur0ubwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-fill" /></template>
