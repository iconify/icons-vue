<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzpbyf_rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzpbyf_rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:luggage-conveyor-belt" /></template>
