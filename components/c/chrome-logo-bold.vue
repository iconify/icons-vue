<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv3bsr2xr.css';
import '../../css/m/mbclv28jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv3bsr2xr"/><path class="mbclv28jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:chrome-logo-bold" /></template>
