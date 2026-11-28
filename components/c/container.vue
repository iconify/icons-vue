<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tna_dgorv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tna_dgorv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:container" /></template>
