<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnd39cc7h.css';
import '../../css/j/j7hpihb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mnd39cc7h"/><path class="j7hpihb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drone-front" /></template>
