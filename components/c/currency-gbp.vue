<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f83ut6b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f83ut6b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-gbp" /></template>
