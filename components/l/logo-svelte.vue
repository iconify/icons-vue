<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arlt_l0ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="arlt_l0ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-svelte" /></template>
