<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnxkxebxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="bnxkxebxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillenine" /></template>
