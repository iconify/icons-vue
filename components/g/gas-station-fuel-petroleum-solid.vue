<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v907xfxmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v907xfxmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:gas-station-fuel-petroleum-solid" /></template>
