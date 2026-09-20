<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca6u321lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca6u321lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-2-fill" /></template>
