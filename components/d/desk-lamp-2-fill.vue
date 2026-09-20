<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtodnibgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xtodnibgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:desk-lamp-2-fill" /></template>
