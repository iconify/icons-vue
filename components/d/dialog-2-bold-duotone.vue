<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcgghzbvl.css';
import '../../css/i/inyn_6bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mcgghzbvl"/><path class="inyn_6bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-2-bold-duotone" /></template>
