<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzogth0ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzogth0ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:health-care-2" /></template>
