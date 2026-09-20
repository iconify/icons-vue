<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj5emybiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nj5emybiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:clipboard" /></template>
