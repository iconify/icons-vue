<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzditrbqy.css';
import '../../css/b/bl1wln6eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="xzditrbqy"/><path class="bl1wln6eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:camera-fill" /></template>
