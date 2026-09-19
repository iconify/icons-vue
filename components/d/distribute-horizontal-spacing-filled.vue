<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1z93w91l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j1z93w91l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:distribute-horizontal-spacing-filled" /></template>
