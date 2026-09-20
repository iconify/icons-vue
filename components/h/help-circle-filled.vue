<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qul541b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qul541b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:help-circle-filled" /></template>
