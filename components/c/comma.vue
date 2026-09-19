<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdan5fs-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":154,"height":767};
const content = `<path class="xdan5fs-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:comma" /></template>
