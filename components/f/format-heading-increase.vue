<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u52euicos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u52euicos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-heading-increase" /></template>
