<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2rnrdb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i2rnrdb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:blockquote-16-solid" /></template>
