<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0x_y24db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r0x_y24db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:file-tray-sharp" /></template>
