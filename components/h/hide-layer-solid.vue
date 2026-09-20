<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz-h2ub-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz-h2ub-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:hide-layer-solid" /></template>
