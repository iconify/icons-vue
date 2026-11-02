<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn3efojqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn3efojqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:down-fill" /></template>
