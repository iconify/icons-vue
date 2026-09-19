<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3tp4bcgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3tp4bcgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:like" /></template>
