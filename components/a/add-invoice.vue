<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtrm-5ano.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtrm-5ano"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-invoice" /></template>
