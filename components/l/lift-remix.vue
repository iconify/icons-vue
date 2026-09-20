<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2h002-cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a2h002-cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lift-remix" /></template>
