<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlxkxxbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlxkxxbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:keyboard-command" /></template>
