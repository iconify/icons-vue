<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9zj9mq8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o9zj9mq8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-under-height-restrictor" /></template>
