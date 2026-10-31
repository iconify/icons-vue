<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugy9pwbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugy9pwbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:baby-fill-round" /></template>
