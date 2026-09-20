<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzk1asbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzk1asbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:data-matrix" /></template>
