<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u1coyrgub.css';
import '../../css/m/mb3gk9bpt.css';
import '../../css/i/ihx2hwbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u1coyrgub"/><path class="mb3gk9bpt"/><path clip-rule="evenodd" class="ihx2hwbnx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bolt-duotone" /></template>
