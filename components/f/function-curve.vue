<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z03z7ycvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z03z7ycvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:function-curve" /></template>
