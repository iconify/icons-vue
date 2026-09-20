<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpc4lacel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wpc4lacel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:coathanger-fill" /></template>
