<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdhqxjbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mdhqxjbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-bookmark" /></template>
