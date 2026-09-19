<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asb-_0zbx.css';
import '../../css/m/m37_gnbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asb-_0zbx"/><path class="m37_gnbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:log-out-circle" /></template>
