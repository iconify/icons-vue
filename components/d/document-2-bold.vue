<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd-1mab0x.css';
import '../../css/u/uypdg1btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vd-1mab0x"/><path class="uypdg1btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-2-bold" /></template>
