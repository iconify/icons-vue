<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9cxw4a1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9cxw4a1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:axe-line" /></template>
