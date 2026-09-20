<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itl92zjdi.css';
import '../../css/r/rtxfoabgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itl92zjdi"/><path class="rtxfoabgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:condicioner-2-bold" /></template>
