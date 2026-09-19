<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toy3fsb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toy3fsb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:luggage-lockers" /></template>
