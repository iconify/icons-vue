<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmibc4bxr.css';
import '../../css/n/nu9w54b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="nu9w54b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:galicia" /></template>
