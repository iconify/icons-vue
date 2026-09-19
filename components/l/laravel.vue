<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85jvzb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f85jvzb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:laravel" /></template>
