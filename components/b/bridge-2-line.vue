<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozic-irzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozic-irzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bridge-2-line" /></template>
