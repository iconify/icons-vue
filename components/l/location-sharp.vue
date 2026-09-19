<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8n_19bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t8n_19bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:location-sharp" /></template>
