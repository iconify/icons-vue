<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_q1xdzts.css';
import '../../css/o/ogmfbzzzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f_q1xdzts"/><path class="ogmfbzzzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deploy" /></template>
