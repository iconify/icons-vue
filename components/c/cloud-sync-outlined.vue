<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3bu2f_4i.css';
import '../../css/k/kl4oqnb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d3bu2f_4i"/><path class="kl4oqnb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:cloud-sync-outlined" /></template>
