<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itva-1bmg.css';
import '../../css/o/o6y24yasb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itva-1bmg"/><path class="o6y24yasb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:brush-sparkles-filled" /></template>
