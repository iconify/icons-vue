<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vghuicoks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vghuicoks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:atproto" /></template>
