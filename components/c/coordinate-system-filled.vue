<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgc1imbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgc1imbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:coordinate-system-filled" /></template>
