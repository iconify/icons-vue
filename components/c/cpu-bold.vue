<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7y0uxbsp.css';
import '../../css/l/l1ebf737s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7y0uxbsp"/><path clip-rule="evenodd" class="l1ebf737s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cpu-bold" /></template>
