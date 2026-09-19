<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7ni9ibas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y7ni9ibas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:format-painter" /></template>
