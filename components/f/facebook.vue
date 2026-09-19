<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6xz5ubre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i6xz5ubre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:facebook" /></template>
