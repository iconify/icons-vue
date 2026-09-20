<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm9149b3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm9149b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:baseball-2-line" /></template>
