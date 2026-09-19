<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8p50493h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k8p50493h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:heart-exclamation" /></template>
