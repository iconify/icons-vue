<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-i3f9bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-i3f9bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:crown" /></template>
