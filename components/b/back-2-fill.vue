<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfkudabgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfkudabgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:back-2-fill" /></template>
