<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnghh3b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nnghh3b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:globe" /></template>
