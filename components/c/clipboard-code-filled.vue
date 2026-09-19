<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l17hfdciu.css';
import '../../css/t/txxclzb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l17hfdciu"/><path class="txxclzb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-code-filled" /></template>
