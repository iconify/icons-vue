<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjj53xb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zjj53xb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:log-remix" /></template>
