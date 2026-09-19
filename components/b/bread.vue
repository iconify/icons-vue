<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aevp-mb1f.css';
import '../../css/e/etbak1bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aevp-mb1f duoicon-secondary-layer"/><path class="duoicon-primary-layer etbak1bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bread" /></template>
