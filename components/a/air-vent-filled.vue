<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8gghnbuu.css';
import '../../css/x/xhxzdg_-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8gghnbuu"/><path clip-rule="evenodd" class="xhxzdg_-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:air-vent-filled" /></template>
