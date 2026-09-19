<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-8l8abkc.css';
import '../../css/y/yts213bsu.css';
import '../../css/m/majk71b5n.css';
import '../../css/o/ow5iplbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l-8l8abkc"/><path class="yts213bsu"/><path class="majk71b5n"/><path class="ow5iplbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dashboard-twotone" /></template>
