<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecn-l84yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecn-l84yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:currency-rupee-duotone-round" /></template>
