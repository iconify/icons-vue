<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvogu3lmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvogu3lmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-left-fill" /></template>
