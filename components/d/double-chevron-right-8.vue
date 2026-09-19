<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3eoygbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k3eoygbat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:double-chevron-right-8" /></template>
