<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlhsvkb_y.css';
import '../../css/p/pkf1_sbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hlhsvkb_y"/><path class="pkf1_sbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockbox-48-bold" /></template>
