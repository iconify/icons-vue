<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7_r22bur.css';
import '../../css/z/zchckjb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7_r22bur"/><path class="zchckjb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:checkmark-circle-fill" /></template>
