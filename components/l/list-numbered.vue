<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1qflhkfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="x1qflhkfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:list-numbered" /></template>
