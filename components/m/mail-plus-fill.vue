<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg_34mb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jg_34mb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-plus-fill" /></template>
