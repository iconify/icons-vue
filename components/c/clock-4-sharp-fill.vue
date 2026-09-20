<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzzkxlb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzzkxlb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-4-sharp-fill" /></template>
