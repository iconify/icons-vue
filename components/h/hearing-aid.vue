<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzyv8xbll.css';
import '../../css/t/t8atr7bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tzyv8xbll"/><path class="t8atr7bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:hearing-aid" /></template>
