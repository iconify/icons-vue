<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhz-jlbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhz-jlbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amcrest-dark" /></template>
