<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv_brepse.css';
import '../../css/g/gjbusdbhw.css';
import '../../css/i/io6m8-o3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yv_brepse"/><path class="gjbusdbhw"/><path class="io6m8-o3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:exclamation-circle-twotone" /></template>
