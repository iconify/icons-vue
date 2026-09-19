<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctyxlqbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctyxlqbdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-fan-light" /></template>
