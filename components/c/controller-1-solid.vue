<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsl032bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qsl032bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:controller-1-solid" /></template>
