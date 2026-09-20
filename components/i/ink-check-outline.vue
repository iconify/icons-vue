<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdv9-dbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdv9-dbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ink-check-outline" /></template>
