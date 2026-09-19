<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odmt8ovdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odmt8ovdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:adore-mirror" /></template>
