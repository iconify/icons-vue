<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q04j8-bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q04j8-bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-settings-spark-remix" /></template>
