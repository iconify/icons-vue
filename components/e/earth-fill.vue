<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jisuh7bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jisuh7bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earth-fill" /></template>
