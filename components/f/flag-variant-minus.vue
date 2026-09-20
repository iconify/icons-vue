<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-elg5b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-elg5b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-variant-minus" /></template>
