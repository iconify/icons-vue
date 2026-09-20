<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3no7gs5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3no7gs5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-xiaomareport-filled" /></template>
