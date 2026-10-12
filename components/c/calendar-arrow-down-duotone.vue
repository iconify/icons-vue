<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ftpujxbdo.css';
import '../../css/u/u_-wtlw1c.css';
import '../../css/p/p3poopb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ftpujxbdo"/><path class="u_-wtlw1c"/><path class="p3poopb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-arrow-down-duotone" /></template>
