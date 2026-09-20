<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y25th20gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y25th20gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:application-add-remix" /></template>
