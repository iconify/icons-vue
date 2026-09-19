<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnl7bw4sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mnl7bw4sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:lark" /></template>
