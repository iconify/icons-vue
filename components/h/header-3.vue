<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scuur4oxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="scuur4oxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:header-3" /></template>
