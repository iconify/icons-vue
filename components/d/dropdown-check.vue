<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1j_wl62j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1j_wl62j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dropdown-check" /></template>
