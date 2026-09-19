<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaz7p-08j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xaz7p-08j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:building" /></template>
