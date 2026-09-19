<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os3dcbbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="os3dcbbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:litecoin-sign" /></template>
