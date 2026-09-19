<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvkixbcpd.css';
import '../../css/i/io4621_ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lvkixbcpd"/><path class="io4621_ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:connection" /></template>
