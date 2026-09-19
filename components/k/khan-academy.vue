<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1f4c38_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1f4c38_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:khan-academy" /></template>
