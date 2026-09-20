<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s91q4ib6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s91q4ib6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-edit" /></template>
