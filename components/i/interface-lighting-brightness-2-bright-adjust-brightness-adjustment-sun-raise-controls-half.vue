<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afgz_374z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="afgz_374z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-lighting-brightness-2-bright-adjust-brightness-adjustment-sun-raise-controls-half" /></template>
