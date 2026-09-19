<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj3ebeb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zj3ebeb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:cool" /></template>
