<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx-cjtjaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zx-cjtjaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-square-fill" /></template>
