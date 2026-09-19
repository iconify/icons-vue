<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym5aslb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":680,"height":642};
const content = `<path class="ym5aslb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bag" /></template>
