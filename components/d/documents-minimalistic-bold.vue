<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym7f000we.css';
import '../../css/g/gv5ke9bho.css';
import '../../css/r/rqzve2bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym7f000we"/><path class="gv5ke9bho"/><path class="rqzve2bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:documents-minimalistic-bold" /></template>
