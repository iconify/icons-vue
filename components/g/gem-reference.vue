<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftv6d47py.css';
import '../../css/l/lz96xw1en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ftv6d47py"/><path class="lz96xw1en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gem-reference" /></template>
