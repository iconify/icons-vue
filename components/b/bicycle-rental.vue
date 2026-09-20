<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql4togbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ql4togbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bicycle-rental" /></template>
