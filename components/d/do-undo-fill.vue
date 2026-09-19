<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlb_rob2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlb_rob2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:do-undo-fill" /></template>
