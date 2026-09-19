<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssqmken7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssqmken7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-03" /></template>
