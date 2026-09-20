<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yms-1bcdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yms-1bcdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:keyboard-option-setting-gear-remix" /></template>
