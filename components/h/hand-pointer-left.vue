<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqtcx1wqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":448};
const content = `<path class="vqtcx1wqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hand-pointer-left" /></template>
