<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra7tqub2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ra7tqub2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bastion-host" /></template>
