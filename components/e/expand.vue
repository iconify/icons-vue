<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkn4d7nbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="xkn4d7nbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:expand" /></template>
