<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi49eh3za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pi49eh3za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:bright-button" /></template>
