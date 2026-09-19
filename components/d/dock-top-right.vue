<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfjb5jbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfjb5jbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-right" /></template>
