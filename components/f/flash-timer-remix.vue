<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eigbs-bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eigbs-bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:flash-timer-remix" /></template>
