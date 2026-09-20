<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwci7jbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xwci7jbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:folder" /></template>
