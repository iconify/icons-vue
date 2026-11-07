<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3l80h-5o.css';
import '../../css/l/l01_od4ep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3l80h-5o"/><path clip-rule="evenodd" class="l01_od4ep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-close-bold-duotone" /></template>
