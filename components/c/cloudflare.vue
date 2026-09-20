<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv53j552d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv53j552d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cloudflare" /></template>
