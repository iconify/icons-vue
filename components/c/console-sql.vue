<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_qcc4bjy.css';
import '../../css/s/s2u7zvnem.css';
import '../../css/w/w13sax6_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b_qcc4bjy"/><path class="s2u7zvnem"/><path class="w13sax6_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:console-sql" /></template>
