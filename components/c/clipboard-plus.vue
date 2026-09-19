<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iti8b_hwb.css';
import '../../css/e/e4rjz7l1i.css';
import '../../css/y/yhv9f2bcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iti8b_hwb"/><path class="e4rjz7l1i"/><path class="yhv9f2bcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:clipboard-plus" /></template>
