<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8bnl6wke.css';
import '../../css/z/zy6g27b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="m8bnl6wke"/><path clip-rule="evenodd" class="zy6g27b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:iphone" /></template>
