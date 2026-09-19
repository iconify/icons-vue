<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh1_d4dql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jh1_d4dql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:end-point-solid" /></template>
