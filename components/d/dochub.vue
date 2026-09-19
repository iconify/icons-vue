<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6--woh2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="b6--woh2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:dochub" /></template>
