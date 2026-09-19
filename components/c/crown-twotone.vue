<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ius3-6n0i.css';
import '../../css/s/srr8t7bum.css';
import '../../css/f/faq8qdvkq.css';
import '../../css/r/rneejsm5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ius3-6n0i"/><path class="srr8t7bum"/><path class="faq8qdvkq"/><path class="rneejsm5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:crown-twotone" /></template>
