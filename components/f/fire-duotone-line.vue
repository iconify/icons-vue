<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9zjytb8k.css';
import '../../css/q/qcmlopf1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9zjytb8k"/><path class="qcmlopf1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:fire-duotone-line" /></template>
