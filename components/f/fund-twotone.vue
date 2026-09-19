<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tozv2lbrl.css';
import '../../css/q/qk8hpubkt.css';
import '../../css/w/w51n_2blg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tozv2lbrl"/><path class="qk8hpubkt"/><path class="w51n_2blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:fund-twotone" /></template>
