<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw6wd9x6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iw6wd9x6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:at-badge-plus" /></template>
