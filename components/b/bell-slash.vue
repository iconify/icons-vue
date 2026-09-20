<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bggwutbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bggwutbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bell-slash" /></template>
