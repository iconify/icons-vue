<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr2u00bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2u00bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-filled" /></template>
