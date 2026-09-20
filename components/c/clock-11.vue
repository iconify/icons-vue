<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mphqjt4dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mphqjt4dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-11" /></template>
