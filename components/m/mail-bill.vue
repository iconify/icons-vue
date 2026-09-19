<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn-044cbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="hn-044cbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mail-bill" /></template>
