<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_jj_0b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v_jj_0b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-rotate-right-1-remix" /></template>
