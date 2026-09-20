<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpcox3bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":141.83};
const content = `<path class="qpcox3bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chase-light" /></template>
