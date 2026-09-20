<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4o5u6otg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4o5u6otg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clapperboard-open-check-outline" /></template>
