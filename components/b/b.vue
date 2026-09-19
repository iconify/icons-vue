<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agrwl2bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":563,"height":768};
const content = `<path class="agrwl2bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:b" /></template>
