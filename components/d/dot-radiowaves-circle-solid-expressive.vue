<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwm5x1bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwm5x1bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dot-radiowaves-circle-solid-expressive" /></template>
