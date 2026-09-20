<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcg8cukwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qcg8cukwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cursor-square-filled" /></template>
