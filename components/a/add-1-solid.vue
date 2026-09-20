<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-4sl_2no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l-4sl_2no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:add-1-solid" /></template>
