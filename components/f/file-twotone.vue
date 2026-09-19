<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux_5wvris.css';
import '../../css/j/jso3jy2en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ux_5wvris"/><path class="jso3jy2en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-twotone" /></template>
