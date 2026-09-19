<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kopjo4b-r.css';
import '../../css/h/hp5x7vfmy.css';
import '../../css/x/xbsqhfb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kopjo4b-r"/><path class="hp5x7vfmy"/><path class="xbsqhfb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:book-twotone" /></template>
