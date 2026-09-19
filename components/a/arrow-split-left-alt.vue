<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbw23ubbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbw23ubbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-split-left-alt" /></template>
