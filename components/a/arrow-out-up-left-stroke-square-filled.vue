<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6gvdlb7i.css';
import '../../css/s/soi_5_bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6gvdlb7i"/><path class="soi_5_bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-left-stroke-square-filled" /></template>
