<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/few52z2af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="few52z2af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cloudflare" /></template>
