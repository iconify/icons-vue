<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nllo96y1n.css';
import '../../css/r/ro4pfvbsr.css';
import '../../css/k/kb3bwobho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nllo96y1n"/><path class="ro4pfvbsr"/><path class="kb3bwobho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-bold" /></template>
