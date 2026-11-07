<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxlp5qvgf.css';
import '../../css/o/ojf0j38zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxlp5qvgf"/><path clip-rule="evenodd" class="ojf0j38zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-outline" /></template>
