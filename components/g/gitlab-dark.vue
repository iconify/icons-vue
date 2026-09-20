<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwvmq7j8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qwvmq7j8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gitlab-dark" /></template>
