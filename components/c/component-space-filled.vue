<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ql564gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ql564gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-space-filled" /></template>
