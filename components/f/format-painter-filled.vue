<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2e1cyb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n2e1cyb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:format-painter-filled" /></template>
