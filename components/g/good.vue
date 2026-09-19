<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqb0x2bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":679};
const content = `<path class="sqb0x2bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:good" /></template>
