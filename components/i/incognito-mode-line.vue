<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnkwypo9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnkwypo9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:incognito-mode-line" /></template>
