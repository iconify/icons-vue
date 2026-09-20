<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh-fv613y.css';
import '../../css/l/leg-f-qxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kh-fv613y"/><path class="leg-f-qxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:log-in-ltr" /></template>
