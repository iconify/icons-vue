<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obk1lubzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obk1lubzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cup-paper-filled" /></template>
