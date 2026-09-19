<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wda5zip_i.css';
import '../../css/z/zlfjm9kls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="wda5zip_i"/><circle transform="rotate(-45 7.435 7.173)" class="zlfjm9kls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:label" /></template>
