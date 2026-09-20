<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m067-7bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m067-7bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circuit-switch-closed" /></template>
