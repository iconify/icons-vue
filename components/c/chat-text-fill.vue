<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5u-odb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n5u-odb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-text-fill" /></template>
