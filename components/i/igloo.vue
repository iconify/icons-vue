<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj-s-r_3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bj-s-r_3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:igloo" /></template>
