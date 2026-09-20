<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu65qx2xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu65qx2xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:ai-terminal-1-filled" /></template>
