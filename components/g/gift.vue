<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipicdkbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipicdkbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:gift" /></template>
