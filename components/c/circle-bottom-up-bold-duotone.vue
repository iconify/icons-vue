<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb90nbxf.css';
import '../../css/d/d-j_pg1wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path clip-rule="evenodd" class="d-j_pg1wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-bottom-up-bold-duotone" /></template>
