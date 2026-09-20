<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw31-9b4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qw31-9b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:kickstarter-k" /></template>
