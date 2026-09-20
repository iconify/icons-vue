<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah4tet64p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah4tet64p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calculator5-filled" /></template>
