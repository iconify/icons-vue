<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywx5vibya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ywx5vibya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:compare-uneven" /></template>
