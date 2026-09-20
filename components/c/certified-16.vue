<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnb1mxbou.css';
import '../../css/q/qxw4ulbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qnb1mxbou"/><path clip-rule="evenodd" class="qxw4ulbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:certified-16" /></template>
