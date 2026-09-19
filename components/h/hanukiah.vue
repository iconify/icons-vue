<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tomm5sbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="tomm5sbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hanukiah" /></template>
