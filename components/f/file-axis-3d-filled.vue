<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl3z5hb3m.css';
import '../../css/y/yyu6w0k1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl3z5hb3m"/><path class="yyu6w0k1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-axis-3d-filled" /></template>
