<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or7lffclf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or7lffclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hotkey-line" /></template>
