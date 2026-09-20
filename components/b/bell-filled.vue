<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzyvu_nxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzyvu_nxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-filled" /></template>
