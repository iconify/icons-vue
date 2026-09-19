<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlnn0ibiz.css';
import '../../css/t/txfhqbbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nlnn0ibiz"/><path class="txfhqbbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:location" /></template>
