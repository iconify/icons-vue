<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quzx1ub2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quzx1ub2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fax-line" /></template>
