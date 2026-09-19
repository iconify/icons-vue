<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6lcxb24u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6lcxb24u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chatbox-sharp" /></template>
