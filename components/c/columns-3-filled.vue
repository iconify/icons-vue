<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbm0q3_fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbm0q3_fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:columns-3-filled" /></template>
