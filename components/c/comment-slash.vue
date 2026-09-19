<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbzxgwq7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="vbzxgwq7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:comment-slash" /></template>
