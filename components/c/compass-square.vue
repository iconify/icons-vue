<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rilib8bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rilib8bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:compass-square" /></template>
