<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0m87kb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z0m87kb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:facebook" /></template>
