<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spyfq2bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="spyfq2bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invio-light" /></template>
