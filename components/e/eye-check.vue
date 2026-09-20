<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn7l3uo8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn7l3uo8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-check" /></template>
