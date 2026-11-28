<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyr_tub4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyr_tub4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ev-charger" /></template>
