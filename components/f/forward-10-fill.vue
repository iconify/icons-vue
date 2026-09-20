<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2_5ntbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2_5ntbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-10-fill" /></template>
