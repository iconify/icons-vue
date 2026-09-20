<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyc8fwb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyc8fwb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-circles-x-sharp" /></template>
