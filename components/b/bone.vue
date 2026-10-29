<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwx6u199w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwx6u199w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bone" /></template>
