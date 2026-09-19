<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7eutrbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7eutrbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:double-up" /></template>
