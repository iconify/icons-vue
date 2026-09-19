<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es1zkkb-o.css';
import '../../css/c/ca3j5lbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="es1zkkb-o"/><path class="ca3j5lbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:appstore-twotone" /></template>
