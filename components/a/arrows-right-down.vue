<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr2g5kbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2g5kbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-right-down" /></template>
