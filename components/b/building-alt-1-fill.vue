<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8kle0b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8kle0b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:building-alt-1-fill" /></template>
