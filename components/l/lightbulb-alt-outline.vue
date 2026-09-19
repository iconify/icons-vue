<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9vpz2bcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9vpz2bcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lightbulb-alt-outline" /></template>
