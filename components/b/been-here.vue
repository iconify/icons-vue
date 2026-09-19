<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1d5a6bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1d5a6bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:been-here" /></template>
