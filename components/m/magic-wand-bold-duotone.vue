<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxk_x0b5m.css';
import '../../css/o/oa5lvwbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxk_x0b5m"/><path class="oa5lvwbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magic-wand-bold-duotone" /></template>
