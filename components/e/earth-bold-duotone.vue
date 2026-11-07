<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrxlgg64z.css';
import '../../css/q/qcdgl6btj.css';
import '../../css/e/e23ts40de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="qcdgl6btj"/><path class="e23ts40de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:earth-bold-duotone" /></template>
