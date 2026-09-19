<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcsm9xb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="lcsm9xb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:local-convenience-store" /></template>
