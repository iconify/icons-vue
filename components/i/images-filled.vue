<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqygs8_op.css';
import '../../css/b/bog62tbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqygs8_op"/><path class="bog62tbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:images-filled" /></template>
