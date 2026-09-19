<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua3rgubbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua3rgubbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:distribute-vertical-center" /></template>
