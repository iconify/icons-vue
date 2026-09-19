<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi3ewdbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xi3ewdbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:branches-outline" /></template>
