<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbn1t2yzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zbn1t2yzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-right-from-bracket" /></template>
