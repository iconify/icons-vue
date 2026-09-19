<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohv39gr8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohv39gr8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-arrow-out-down-left" /></template>
