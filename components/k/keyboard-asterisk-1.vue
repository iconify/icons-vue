<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvm6k-5fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvm6k-5fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:keyboard-asterisk-1" /></template>
