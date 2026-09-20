<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flf719bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flf719bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-remove-outline" /></template>
