<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-z8-fb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-z8-fb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:land-rows-horizontal" /></template>
