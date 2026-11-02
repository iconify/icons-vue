<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahih2qpzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahih2qpzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-panel-top-line" /></template>
