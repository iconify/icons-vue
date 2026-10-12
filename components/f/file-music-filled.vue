<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1hwd0eh.css';
import '../../css/l/l2zpy5eyh.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1hwd0eh"/><path class="l2zpy5eyh"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-music-filled" /></template>
