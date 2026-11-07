<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laypnctxv.css';
import '../../css/p/pqht0qb6q.css';
import '../../css/e/eb9uwtqnk.css';
import '../../css/f/fwy-nwbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="laypnctxv"/><path clip-rule="evenodd" class="pqht0qb6q"/><path class="eb9uwtqnk"/><path clip-rule="evenodd" class="fwy-nwbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bedside-table-bold-duotone" /></template>
