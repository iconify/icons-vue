<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0-ck1g3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e0-ck1g3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:calculator" /></template>
