<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m40w_1l6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m40w_1l6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crowdsec-manager-light" /></template>
