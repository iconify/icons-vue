<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx714ckou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sx714ckou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-to-line-alt" /></template>
