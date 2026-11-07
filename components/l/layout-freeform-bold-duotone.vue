<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxbhz1bxu.css';
import '../../css/w/w482_wbjc.css';
import '../../css/z/zs0elrbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxbhz1bxu"/><path class="w482_wbjc"/><path class="zs0elrbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layout-freeform-bold-duotone" /></template>
