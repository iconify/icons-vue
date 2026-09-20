<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgbl4_qde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgbl4_qde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-exclamation" /></template>
