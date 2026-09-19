<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tffw4rreh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tffw4rreh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-split-up" /></template>
