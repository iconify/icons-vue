<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k98gnnbfh.css';
import '../../css/v/voeniibqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k98gnnbfh"/><path class="voeniibqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-bold" /></template>
