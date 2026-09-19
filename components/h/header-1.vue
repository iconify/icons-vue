<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq0ks_b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oq0ks_b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:header-1" /></template>
