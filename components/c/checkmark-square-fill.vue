<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ct0bzjh.css';
import '../../css/b/bkce-3brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ct0bzjh"/><path class="bkce-3brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:checkmark-square-fill" /></template>
