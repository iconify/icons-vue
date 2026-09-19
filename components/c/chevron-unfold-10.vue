<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pali_db3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pali_db3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-unfold-10" /></template>
