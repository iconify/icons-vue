<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhehljbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhehljbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-up-down-circle-filled" /></template>
