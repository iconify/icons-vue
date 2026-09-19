<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2fefybui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":672};
const content = `<path class="x2fefybui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:login" /></template>
