<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7zcvj1fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7zcvj1fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-remove" /></template>
