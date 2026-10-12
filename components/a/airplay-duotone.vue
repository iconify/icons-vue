<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m7ter5dcd.css';
import '../../css/l/ly4csrbrb.css';
import '../../css/k/kdpj9eb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m7ter5dcd"/><path class="ly4csrbrb"/><path class="kdpj9eb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:airplay-duotone" /></template>
