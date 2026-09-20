<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lejmtw8sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lejmtw8sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-more-alt-duotone" /></template>
