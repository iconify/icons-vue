<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irpf0cyiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irpf0cyiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:beaker" /></template>
