<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms98do_7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ms98do_7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:comment-slash" /></template>
