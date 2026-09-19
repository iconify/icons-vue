<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejn5f_bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejn5f_bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hot-dog" /></template>
