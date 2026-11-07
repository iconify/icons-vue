<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl79juz7d.css';
import '../../css/i/i3l80h-5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl79juz7d"/><path class="i3l80h-5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-check-bold-duotone" /></template>
