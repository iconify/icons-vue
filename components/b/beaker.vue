<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a12w9vk-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a12w9vk-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:beaker" /></template>
