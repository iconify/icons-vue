<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tozv2lbrl.css';
import '../../css/k/krpi41bzj.css';
import '../../css/w/w53f1mbdp.css';
import '../../css/b/bg879tbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tozv2lbrl"/><path class="krpi41bzj"/><path class="w53f1mbdp"/><path class="bg879tbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:idcard-twotone" /></template>
