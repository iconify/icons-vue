<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh53_dbyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh53_dbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copilot-fill" /></template>
