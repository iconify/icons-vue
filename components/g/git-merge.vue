<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te_k_zb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="te_k_zb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:git-merge" /></template>
