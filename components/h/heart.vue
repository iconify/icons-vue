<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk0b5pbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bk0b5pbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:heart" /></template>
