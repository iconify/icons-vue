<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jod_b1bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jod_b1bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:database-refresh-solid" /></template>
