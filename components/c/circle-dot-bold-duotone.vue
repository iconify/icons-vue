<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxlgg64z.css';
import '../../css/e/er9_2_bjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="er9_2_bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-dot-bold-duotone" /></template>
