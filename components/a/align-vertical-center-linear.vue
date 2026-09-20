<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dzle42rhc.css';
import '../../css/e/eox6dq53k.css';
import '../../css/k/kah-p9bbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dzle42rhc"/><path class="eox6dq53k"/><path class="kah-p9bbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-center-linear" /></template>
