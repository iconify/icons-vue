<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dap5e4boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dap5e4boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:edit-alt-solid" /></template>
