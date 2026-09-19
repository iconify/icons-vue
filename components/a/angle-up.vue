<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh7wvsr7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lh7wvsr7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:angle-up" /></template>
