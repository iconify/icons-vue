<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmp8azpko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmp8azpko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-smile" /></template>
