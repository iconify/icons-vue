<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1m-5accb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t1m-5accb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:fountain" /></template>
