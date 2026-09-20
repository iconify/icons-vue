<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvimrhqnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lvimrhqnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-left-solid" /></template>
