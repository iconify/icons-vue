<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvof47lrw.css';
import '../../css/j/jtcikdbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tvof47lrw"/><path class="jtcikdbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:api-twotone" /></template>
