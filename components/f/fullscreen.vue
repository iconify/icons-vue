<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar8np1bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ar8np1bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:fullscreen" /></template>
