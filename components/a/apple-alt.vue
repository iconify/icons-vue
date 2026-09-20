<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiaoqdbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiaoqdbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:apple-alt" /></template>
