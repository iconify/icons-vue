<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xphz65ecl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xphz65ecl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:consellation-remix" /></template>
