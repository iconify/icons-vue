<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld5lf-b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ld5lf-b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:laravel-nova" /></template>
