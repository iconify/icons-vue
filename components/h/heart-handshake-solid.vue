<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gshwhhb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gshwhhb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heart-handshake-solid" /></template>
