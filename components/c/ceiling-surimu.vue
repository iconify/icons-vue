<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_u14isu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el_u14isu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-surimu" /></template>
