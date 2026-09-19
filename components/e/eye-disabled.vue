<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9j4rgb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d9j4rgb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:eye-disabled" /></template>
