<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpwzb9bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fpwzb9bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-fill" /></template>
