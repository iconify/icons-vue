<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw0chlb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zw0chlb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:dashboard-3-flat" /></template>
