<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn0m8zb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="wn0m8zb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:flag" /></template>
