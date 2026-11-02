<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpnedebau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpnedebau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heart-off-fill" /></template>
