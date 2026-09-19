<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axque105x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="axque105x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:blogger" /></template>
