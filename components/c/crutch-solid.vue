<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktbh_1ykl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ktbh_1ykl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:crutch-solid" /></template>
