<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj2p_abnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj2p_abnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:ice-water" /></template>
