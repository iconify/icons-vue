<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg-1y-bay.css';
import '../../css/x/xszw9heki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg-1y-bay"/><path class="xszw9heki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-copy-filled" /></template>
