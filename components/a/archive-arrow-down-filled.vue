<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moy2mkktn.css';
import '../../css/r/rhjy80e-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="moy2mkktn"/><path class="rhjy80e-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:archive-arrow-down-filled" /></template>
