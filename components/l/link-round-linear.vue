<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbmcrcl1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbmcrcl1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-linear" /></template>
