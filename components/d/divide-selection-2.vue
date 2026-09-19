<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnqhf--ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnqhf--ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:divide-selection-2" /></template>
