<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-s3mkbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-s3mkbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:format-quote" /></template>
