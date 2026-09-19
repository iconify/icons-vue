<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcjfnqwrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wcjfnqwrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-to-line-alt" /></template>
