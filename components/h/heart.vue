<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq1q7fzgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mq1q7fzgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:heart" /></template>
