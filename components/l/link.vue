<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5-cm9x3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5-cm9x3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:link" /></template>
