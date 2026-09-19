<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uagpf0bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uagpf0bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:caret-bottom" /></template>
