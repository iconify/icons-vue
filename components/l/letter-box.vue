<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qia54wv4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qia54wv4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:letter-box" /></template>
