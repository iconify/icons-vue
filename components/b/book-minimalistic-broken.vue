<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rkviku0vk.css';
import '../../css/p/paayxvxde.css';
import '../../css/r/rw8hl94tg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rkviku0vk"/><path class="paayxvxde"/><path class="rw8hl94tg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-minimalistic-broken" /></template>
