<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bss0__tpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bss0__tpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hierarchy-4-solid" /></template>
