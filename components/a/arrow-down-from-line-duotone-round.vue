<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehfx4sj_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehfx4sj_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-from-line-duotone-round" /></template>
