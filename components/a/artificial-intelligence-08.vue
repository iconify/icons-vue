<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta9uj4b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta9uj4b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:artificial-intelligence-08" /></template>
