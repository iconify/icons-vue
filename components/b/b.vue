<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbkx6sbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="bbkx6sbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:b" /></template>
