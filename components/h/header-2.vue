<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5xulob4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x5xulob4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:header-2" /></template>
