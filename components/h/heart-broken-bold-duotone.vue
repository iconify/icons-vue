<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwbwyza6z.css';
import '../../css/w/wo_81unih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwbwyza6z"/><path class="wo_81unih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-broken-bold-duotone" /></template>
