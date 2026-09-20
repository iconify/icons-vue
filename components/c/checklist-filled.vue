<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi_ta4byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vi_ta4byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:checklist-filled" /></template>
