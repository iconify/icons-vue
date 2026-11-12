<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8u43xb9m.css';
import '../../css/i/iid8cxbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8u43xb9m"/><path class="iid8cxbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:centos-dark" /></template>
