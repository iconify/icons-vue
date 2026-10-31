<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl7697j7m.css';
import '../../css/x/x4jxcf4cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="dl7697j7m"/><path class="x4jxcf4cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bahrain" /></template>
