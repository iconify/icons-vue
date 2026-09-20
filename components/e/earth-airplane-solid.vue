<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv0wjcc0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mv0wjcc0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:earth-airplane-solid" /></template>
