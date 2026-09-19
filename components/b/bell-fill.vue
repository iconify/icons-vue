<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3iaynbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u3iaynbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:bell-fill" /></template>
