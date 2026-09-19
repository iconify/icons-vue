<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6atusy8s.css';
import '../../css/r/ra7jfzloj.css';
import '../../css/h/hcj3z71ba.css';
import '../../css/e/etst7gbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d6atusy8s"/><path class="ra7jfzloj"/><path class="hcj3z71ba"/><path class="etst7gbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:diff-twotone" /></template>
