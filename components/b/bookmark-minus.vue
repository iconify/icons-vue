<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpg076mjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpg076mjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:bookmark-minus" /></template>
