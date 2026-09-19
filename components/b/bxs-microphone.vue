<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl7t8bcmf.css';
import '../../css/y/yzdqdzd3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl7t8bcmf"/><path class="yzdqdzd3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-microphone" /></template>
