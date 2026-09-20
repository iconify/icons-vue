<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glyhv4jss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="glyhv4jss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:elevator-solid" /></template>
