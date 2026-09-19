<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcrfoj4kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="lcrfoj4kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ellipsis-circle-fill" /></template>
