<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhcvz-r0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhcvz-r0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-2-bold" /></template>
