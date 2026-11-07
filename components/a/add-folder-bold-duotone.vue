<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flc299r4o.css';
import '../../css/s/sy2gigbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flc299r4o"/><path class="sy2gigbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-folder-bold-duotone" /></template>
