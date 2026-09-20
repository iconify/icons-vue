<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm3_gfbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm3_gfbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:check-check" /></template>
