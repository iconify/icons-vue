<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/supqw7enb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="supqw7enb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:iphone" /></template>
