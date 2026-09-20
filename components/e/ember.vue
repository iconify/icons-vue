<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9v7t8xls.css';
import '../../css/o/os0e1fbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":213};
const content = `<path class="h9v7t8xls"/><path class="os0e1fbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ember" /></template>
