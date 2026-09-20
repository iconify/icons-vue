<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_81m919d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c_81m919d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-lock-remix" /></template>
