<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut1a-rj1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut1a-rj1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-filament-alt" /></template>
