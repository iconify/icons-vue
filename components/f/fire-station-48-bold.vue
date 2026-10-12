<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fui3mb06j.css';
import '../../css/z/zgffl4lji.css';
import '../../css/i/i_ixh4b2n.css';
import '../../css/t/t6015cucx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fui3mb06j"/><path class="zgffl4lji"/><path class="i_ixh4b2n"/><path class="t6015cucx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fire-station-48-bold" /></template>
