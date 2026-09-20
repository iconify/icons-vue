<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfg6--vbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfg6--vbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:laurel-wreath-3-filled" /></template>
