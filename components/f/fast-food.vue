<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekcb3b0rz.css';
import '../../css/j/jfwgpxqzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekcb3b0rz"/><path class="jfwgpxqzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fast-food" /></template>
