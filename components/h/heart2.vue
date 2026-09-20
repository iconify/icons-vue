<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qula-vb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qula-vb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:heart2" /></template>
