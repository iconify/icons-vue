<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeuiky0sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeuiky0sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-diagonal-2" /></template>
