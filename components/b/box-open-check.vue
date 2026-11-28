<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iimok1l1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iimok1l1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:box-open-check" /></template>
