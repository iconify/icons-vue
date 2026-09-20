<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7wvxmbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q7wvxmbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:chess-bishop-remix" /></template>
