<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbl3sx6_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sbl3sx6_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:external-git" /></template>
