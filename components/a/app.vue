<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxxg56hwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":731};
const content = `<path class="gxxg56hwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:app" /></template>
