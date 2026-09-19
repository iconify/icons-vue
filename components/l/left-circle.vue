<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4ofafy9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="p4ofafy9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:left-circle" /></template>
