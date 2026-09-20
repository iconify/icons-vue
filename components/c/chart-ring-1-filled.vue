<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l67lj9z9h.css';
import '../../css/e/eucgmebad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l67lj9z9h"/><path class="eucgmebad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-ring-1-filled" /></template>
