<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk4ud8bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":468,"height":512};
const content = `<path class="zk4ud8bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:codecov" /></template>
