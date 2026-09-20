<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-grs3ykq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-grs3ykq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bread-filled" /></template>
