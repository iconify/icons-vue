<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgcif9d1i.css';
import '../../css/j/jpcgvbsnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgcif9d1i"/><path class="jpcgvbsnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:compass-1-filled" /></template>
