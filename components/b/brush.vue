<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edv7ufw0p.css';
import '../../css/r/r82uqwr_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer edv7ufw0p"/><path class="duoicon-secondary-layer r82uqwr_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:brush" /></template>
