<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrz19cbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrz19cbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-check" /></template>
