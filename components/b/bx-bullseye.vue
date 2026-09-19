<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v62_-3b9x.css';
import '../../css/n/nwfaqcbac.css';
import '../../css/e/ez0pggbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v62_-3b9x"/><path class="nwfaqcbac"/><path class="ez0pggbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bullseye" /></template>
