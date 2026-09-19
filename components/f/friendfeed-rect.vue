<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txlz-ovvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="txlz-ovvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:friendfeed-rect" /></template>
