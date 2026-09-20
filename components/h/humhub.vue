<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlhk7wqxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlhk7wqxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:humhub" /></template>
