<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwoo6cbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pwoo6cbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:double-exclamation-mark" /></template>
