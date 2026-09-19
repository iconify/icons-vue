<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9zm6nblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y9zm6nblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:bat" /></template>
