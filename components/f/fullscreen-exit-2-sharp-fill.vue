<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1d79ebop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1d79ebop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-2-sharp-fill" /></template>
