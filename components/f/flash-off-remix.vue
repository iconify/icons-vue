<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5sibvbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q5sibvbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flash-off-remix" /></template>
