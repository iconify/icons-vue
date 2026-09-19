<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhm7ikbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xhm7ikbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:function" /></template>
