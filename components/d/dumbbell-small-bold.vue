<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy0dji3-w.css';
import '../../css/o/o5dx87whx.css';
import '../../css/c/c5kg7bbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy0dji3-w"/><path class="o5dx87whx"/><path class="c5kg7bbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-small-bold" /></template>
