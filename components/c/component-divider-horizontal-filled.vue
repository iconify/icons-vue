<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny93yw8fe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny93yw8fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:component-divider-horizontal-filled" /></template>
