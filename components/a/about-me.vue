<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8w9h5qwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i8w9h5qwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:about-me" /></template>
