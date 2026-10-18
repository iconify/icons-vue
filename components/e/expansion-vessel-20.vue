<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4aws_orj.css';
import '../../css/l/l-h9c6bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q4aws_orj"/><path class="l-h9c6bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:expansion-vessel-20" /></template>
