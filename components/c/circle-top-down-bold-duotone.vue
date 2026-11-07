<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/s/sh-3ee_ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path clip-rule="evenodd" class="sh-3ee_ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-top-down-bold-duotone" /></template>
