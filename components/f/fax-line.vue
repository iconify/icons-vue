<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e97y7kbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e97y7kbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fax-line" /></template>
