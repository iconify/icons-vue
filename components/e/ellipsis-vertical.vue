<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbncdkb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rbncdkb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ellipsis-vertical" /></template>
