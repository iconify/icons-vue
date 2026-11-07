<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi3uxcbzc.css';
import '../../css/d/duqz644oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi3uxcbzc"/><path class="duqz644oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-to-line-bold-duotone" /></template>
