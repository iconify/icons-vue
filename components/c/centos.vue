<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfqn_kb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kfqn_kb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:centos" /></template>
