<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx7416blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hx7416blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:light-up" /></template>
