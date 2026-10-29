<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i52o7bbpp.css';
import '../../css/t/tpmoddcaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i52o7bbpp wm-k"/><path class="tpmoddcaw wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-right" /></template>
