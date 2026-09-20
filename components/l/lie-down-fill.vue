<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hycozmbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hycozmbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lie-down-fill" /></template>
