<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3w42fqxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j3w42fqxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:close-circle-filled" /></template>
