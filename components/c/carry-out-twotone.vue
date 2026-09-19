<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuk6t8bzw.css';
import '../../css/n/nxma1vbuk.css';
import '../../css/x/xaosrk3sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kuk6t8bzw"/><path class="nxma1vbuk"/><path class="xaosrk3sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:carry-out-twotone" /></template>
