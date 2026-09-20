<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4tx561kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4tx561kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:banknote2" /></template>
