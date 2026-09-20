<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3mex-bdg.css';
import '../../css/l/l-9tsmbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3mex-bdg"/><path class="l-9tsmbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:home-filled" /></template>
