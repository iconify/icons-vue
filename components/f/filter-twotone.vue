<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdxpj0wua.css';
import '../../css/t/tpginfnmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cdxpj0wua"/><path class="tpginfnmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:filter-twotone" /></template>
