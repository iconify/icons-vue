<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plg_1db1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="plg_1db1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:child" /></template>
